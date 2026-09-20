<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz44edbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zz44edbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cachyos" {...props}></Icon>
