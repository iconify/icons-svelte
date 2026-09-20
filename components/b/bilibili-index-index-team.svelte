<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u08vxnw-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u08vxnw-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:bilibili-index-index-team" {...props}></Icon>
