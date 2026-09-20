<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isyu6z9ux.css';
import '../../css/z/zl5x12lyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="isyu6z9ux"/><path class="zl5x12lyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dynamodb-dashboard-light" {...props}></Icon>
