<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddbth32bh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddbth32bh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:reply-solid" {...props}></Icon>
