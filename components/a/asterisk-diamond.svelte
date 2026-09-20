<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr_225bji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cr_225bji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:asterisk-diamond" {...props}></Icon>
