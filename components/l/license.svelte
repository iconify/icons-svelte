<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1_hp2bch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="s1_hp2bch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:license" {...props}></Icon>
