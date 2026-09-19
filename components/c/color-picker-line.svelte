<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rydklwuel.css';
import '../../css/z/zn61f8zew.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 rydklwuel"/><path class="clr-i-outline clr-i-outline-path-2 zn61f8zew"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:color-picker-line" {...props}></Icon>
