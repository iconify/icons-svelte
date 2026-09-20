<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cim5zuk_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cim5zuk_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:paysafe" {...props}></Icon>
