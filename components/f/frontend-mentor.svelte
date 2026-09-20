<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctiyjebru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctiyjebru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:frontend-mentor" {...props}></Icon>
