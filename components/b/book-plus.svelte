<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u53v_5bma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u53v_5bma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:book-plus" {...props}></Icon>
