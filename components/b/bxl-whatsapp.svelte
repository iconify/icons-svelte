<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn2rljbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mn2rljbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-whatsapp" {...props}></Icon>
