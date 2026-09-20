<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvrgnz8qg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xvrgnz8qg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:control-buttons-skip-forward-2" {...props}></Icon>
