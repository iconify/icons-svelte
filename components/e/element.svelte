<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs4emibqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="hs4emibqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:element" {...props}></Icon>
