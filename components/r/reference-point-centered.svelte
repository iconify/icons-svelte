<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wal1i4bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wal1i4bpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:reference-point-centered" {...props}></Icon>
