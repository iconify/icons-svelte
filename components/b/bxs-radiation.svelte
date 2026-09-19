<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em9miyxzj.css';
import '../../css/v/v4i2ew1ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="em9miyxzj"/><circle class="v4i2ew1ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-radiation" {...props}></Icon>
