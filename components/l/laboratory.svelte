<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k19k3sbft.css';
import '../../css/v/v2uff_sgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="k19k3sbft"/><path class="v2uff_sgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:laboratory" {...props}></Icon>
