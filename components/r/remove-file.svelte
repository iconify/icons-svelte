<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/foa7vwb3f.css';
import '../../css/p/puxm9jbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="foa7vwb3f"/><path class="puxm9jbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:remove-file" {...props}></Icon>
