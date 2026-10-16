<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-3_n6vyt.css';
import '../../css/x/x2br98bbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b-3_n6vyt"/><path class="x2br98bbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chisel-48" {...props}></Icon>
