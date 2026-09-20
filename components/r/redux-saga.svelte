<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6fg1dn4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6fg1dn4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:redux-saga" {...props}></Icon>
