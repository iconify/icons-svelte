<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg-_dywku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yg-_dywku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:bed" {...props}></Icon>
