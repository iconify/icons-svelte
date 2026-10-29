<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twy10abre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twy10abre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:list-ordered-solid" {...props}></Icon>
