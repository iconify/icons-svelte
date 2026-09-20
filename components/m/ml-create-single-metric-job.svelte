<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n90uq3bfu.css';
import '../../css/i/i1qy2-bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n90uq3bfu"/><path class="i1qy2-bfm ouiIcon__fillSecondary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:ml-create-single-metric-job" {...props}></Icon>
