<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo-8an5zz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo-8an5zz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mastodon-fill" {...props}></Icon>
