<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oib75js9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oib75js9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:clouderror" {...props}></Icon>
