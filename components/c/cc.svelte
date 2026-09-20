<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gk07qcbce.css';
import '../../css/c/cyflbfbns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gk07qcbce"/><path class="cyflbfbns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:cc" {...props}></Icon>
