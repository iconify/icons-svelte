<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuzx80lqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nuzx80lqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dog-sitting-wearing-collar-and-question-mark" {...props}></Icon>
