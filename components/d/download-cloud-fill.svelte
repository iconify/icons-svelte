<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxk9dhkgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxk9dhkgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:download-cloud-fill" {...props}></Icon>
