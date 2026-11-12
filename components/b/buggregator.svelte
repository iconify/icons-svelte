<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twbai2bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="twbai2bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:buggregator" {...props}></Icon>
