<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0qphggqc.css';
import '../../css/j/jnqqvnouk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0qphggqc"/><path class="jnqqvnouk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:doc2x" {...props}></Icon>
