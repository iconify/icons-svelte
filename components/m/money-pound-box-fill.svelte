<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hao75bc9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hao75bc9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:money-pound-box-fill" {...props}></Icon>
