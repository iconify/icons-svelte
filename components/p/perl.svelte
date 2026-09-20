<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq_olcclz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fq_olcclz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:perl" {...props}></Icon>
