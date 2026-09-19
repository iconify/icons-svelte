<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky3hg7kgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ky3hg7kgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:kusto" {...props}></Icon>
