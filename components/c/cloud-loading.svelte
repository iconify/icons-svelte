<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c521n5b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c521n5b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cloud-loading" {...props}></Icon>
