<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-b_tb_2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-b_tb_2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mega" {...props}></Icon>
