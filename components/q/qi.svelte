<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cof72cpry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cof72cpry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:qi" {...props}></Icon>
