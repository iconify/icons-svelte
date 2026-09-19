<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgwizui3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":29,"height":24};
const content = `<path class="dgwizui3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:center-align" {...props}></Icon>
