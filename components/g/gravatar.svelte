<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltgdkjxtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ltgdkjxtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:gravatar" {...props}></Icon>
