<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq8qkhbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vq8qkhbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:alert-fill-24" {...props}></Icon>
