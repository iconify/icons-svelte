<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2ns4mb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x2ns4mb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:question-mark" {...props}></Icon>
