<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba8lvwbib.css';
import '../../css/e/ef5ug6bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba8lvwbib"/><path class="ef5ug6bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:cloud-check-duotone" {...props}></Icon>
