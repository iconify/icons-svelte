<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj53ek41s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wj53ek41s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:featherlessdotai" {...props}></Icon>
