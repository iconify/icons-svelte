<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5bs2jbns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":989,"height":1000};
const content = `<path class="t5bs2jbns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:docs-landscape" {...props}></Icon>
