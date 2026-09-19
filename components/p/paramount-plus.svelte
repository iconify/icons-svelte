<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh90xkbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eh90xkbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:paramount-plus" {...props}></Icon>
