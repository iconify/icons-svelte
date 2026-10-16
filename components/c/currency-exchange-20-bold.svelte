<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni7oe8l5n.css';
import '../../css/c/c7c-kxbrc.css';
import '../../css/r/rqodbzvhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ni7oe8l5n"/><path class="c7c-kxbrc"/><path class="rqodbzvhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:currency-exchange-20-bold" {...props}></Icon>
