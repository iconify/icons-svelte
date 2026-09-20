<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4tm_e4lw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4tm_e4lw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:brand-codepen-solid" {...props}></Icon>
