<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf_qqhb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gf_qqhb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:laravel-nova" {...props}></Icon>
