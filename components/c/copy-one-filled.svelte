<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7y8xtb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="l7y8xtb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:copy-one-filled" {...props}></Icon>
