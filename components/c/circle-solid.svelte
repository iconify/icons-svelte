<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyw-wccpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyw-wccpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:circle-solid" {...props}></Icon>
