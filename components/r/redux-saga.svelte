<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuk24k_kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuk24k_kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:redux-saga" {...props}></Icon>
