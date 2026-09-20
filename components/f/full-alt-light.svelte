<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abvt66b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abvt66b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:full-alt-light" {...props}></Icon>
