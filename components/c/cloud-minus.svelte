<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba8lvwbib.css';
import '../../css/r/r9ontxjrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba8lvwbib"/><path class="r9ontxjrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:cloud-minus" {...props}></Icon>
