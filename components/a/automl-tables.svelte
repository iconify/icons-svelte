<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8wg0cc7n.css';
import '../../css/r/r_s901bbt.css';
import '../../css/y/yp1ozz1bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8wg0cc7n"/><path class="r_s901bbt"/><path class="yp1ozz1bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:automl-tables" {...props}></Icon>
