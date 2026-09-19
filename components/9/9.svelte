<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw2os6bdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rw2os6bdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:9" {...props}></Icon>
