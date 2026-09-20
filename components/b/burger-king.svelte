<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqoj9abcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqoj9abcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:burger-king" {...props}></Icon>
