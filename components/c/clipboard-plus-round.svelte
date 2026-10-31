<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfzeh9bqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfzeh9bqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clipboard-plus-round" {...props}></Icon>
