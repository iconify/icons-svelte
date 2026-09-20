<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzgw-yejf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vzgw-yejf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:like-bold" {...props}></Icon>
