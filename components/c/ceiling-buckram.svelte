<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a--3-lbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a--3-lbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceiling-buckram" {...props}></Icon>
