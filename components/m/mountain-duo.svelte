<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn2ejlbtm.css';
import '../../css/e/eu7gmyhby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qn2ejlbtm secondary"/><path class="eu7gmyhby primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mountain-duo" {...props}></Icon>
