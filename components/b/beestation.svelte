<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okdhzpq9i.css';
import '../../css/s/skok2lbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="okdhzpq9i"/><path class="skok2lbcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:beestation" {...props}></Icon>
