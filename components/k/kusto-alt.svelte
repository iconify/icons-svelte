<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2e2c-bxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e2e2c-bxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:kusto-alt" {...props}></Icon>
