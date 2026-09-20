<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prnpfqb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="prnpfqb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bookorbit-dark" {...props}></Icon>
