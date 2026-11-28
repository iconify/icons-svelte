<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql2qn_7vp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ql2qn_7vp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square-x-solid" {...props}></Icon>
