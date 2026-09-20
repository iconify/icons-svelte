<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxwrar36v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxwrar36v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:remove-bold-bold" {...props}></Icon>
