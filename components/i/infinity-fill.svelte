<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3a90gpfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3a90gpfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:infinity-fill" {...props}></Icon>
