<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrxmklb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrxmklb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-play-solid" {...props}></Icon>
