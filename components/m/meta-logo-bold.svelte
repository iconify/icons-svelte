<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2g07ihhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r2g07ihhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:meta-logo-bold" {...props}></Icon>
