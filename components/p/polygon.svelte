<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iggf-lgsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iggf-lgsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:polygon" {...props}></Icon>
