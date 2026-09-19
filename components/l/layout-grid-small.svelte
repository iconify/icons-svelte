<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phz_w4bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phz_w4bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:layout-grid-small" {...props}></Icon>
