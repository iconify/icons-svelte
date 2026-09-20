<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgz4_hbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qgz4_hbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:lock-semi-open-16-solid" {...props}></Icon>
