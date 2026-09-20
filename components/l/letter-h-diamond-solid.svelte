<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyhafj-ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyhafj-ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-h-diamond-solid" {...props}></Icon>
