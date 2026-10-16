<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4-_f1bng.css';
import '../../css/c/ccwmrkkue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z4-_f1bng"/><path class="ccwmrkkue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folders-48" {...props}></Icon>
