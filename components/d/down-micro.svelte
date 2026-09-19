<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3vg0rc7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":471,"height":1000};
const content = `<path class="s3vg0rc7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:down-micro" {...props}></Icon>
