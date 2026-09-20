<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k36vwxhpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k36vwxhpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rolls-royce" {...props}></Icon>
