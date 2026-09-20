<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/illioo3jp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="illioo3jp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:flatpak" {...props}></Icon>
