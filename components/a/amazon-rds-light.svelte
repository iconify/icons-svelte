<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7ql9-bef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o7ql9-bef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon-rds-light" {...props}></Icon>
