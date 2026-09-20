<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gty-j1j5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gty-j1j5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:academia" {...props}></Icon>
