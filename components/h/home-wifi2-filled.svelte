<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrmpk-mlb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rrmpk-mlb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:home-wifi2-filled" {...props}></Icon>
