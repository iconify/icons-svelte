<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxd1sc-xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxd1sc-xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:home-check" {...props}></Icon>
