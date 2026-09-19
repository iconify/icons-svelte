<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csk2dwbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":520,"height":512};
const content = `<path class="csk2dwbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:do-not-wring" {...props}></Icon>
