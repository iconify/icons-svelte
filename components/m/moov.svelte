<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzmusacjq.css';
import '../../css/k/ks466_bpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzmusacjq"/><path class="ks466_bpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:moov" {...props}></Icon>
