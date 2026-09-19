<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t03cpykmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t03cpykmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-dev-to" {...props}></Icon>
