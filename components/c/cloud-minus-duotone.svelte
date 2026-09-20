<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba8lvwbib.css';
import '../../css/f/fmuqr9b0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba8lvwbib"/><path class="fmuqr9b0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:cloud-minus-duotone" {...props}></Icon>
