<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg7zddbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wg7zddbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lumx" {...props}></Icon>
