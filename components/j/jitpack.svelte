<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn-_cztfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zn-_cztfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jitpack" {...props}></Icon>
