<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw0-01btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vw0-01btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:blocks" {...props}></Icon>
