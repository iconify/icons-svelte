<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crrtghkve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crrtghkve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:fat-arrow-up-left" {...props}></Icon>
