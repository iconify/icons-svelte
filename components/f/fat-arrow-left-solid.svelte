<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekqu4_gnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekqu4_gnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:fat-arrow-left-solid" {...props}></Icon>
