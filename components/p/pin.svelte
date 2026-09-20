<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy4414bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zy4414bsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:pin" {...props}></Icon>
