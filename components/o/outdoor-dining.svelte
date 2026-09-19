<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyj3-clpj.css';
import '../../css/t/tfo6zr1jo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eyj3-clpj"/><path class="tfo6zr1jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:outdoor-dining" {...props}></Icon>
