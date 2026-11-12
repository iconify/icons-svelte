<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix-pf_jrx.css';
import '../../css/s/s8ttcqbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ix-pf_jrx"/><path class="s8ttcqbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kubernetes" {...props}></Icon>
