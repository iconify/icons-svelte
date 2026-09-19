<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5l4uj3dn.css';
import '../../css/q/q-lo6_bbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":24};
const content = `<path class="i5l4uj3dn"/><path class="q-lo6_bbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:hotel-alt" {...props}></Icon>
