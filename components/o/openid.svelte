<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw5hcaclv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":472};
const content = `<path class="qw5hcaclv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:openid" {...props}></Icon>
