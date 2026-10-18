<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypuxbw7af.css';
import '../../css/a/awuv256_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ypuxbw7af"/><path class="awuv256_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:green-jobs-48" {...props}></Icon>
