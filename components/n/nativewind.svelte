<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irumnccxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irumnccxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nativewind" {...props}></Icon>
