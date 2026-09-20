<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf_itvb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gf_itvb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:expand-down-filled" {...props}></Icon>
