<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnilq3uxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qnilq3uxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:info-circle-light" {...props}></Icon>
