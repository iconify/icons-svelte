<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfw-zbcoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfw-zbcoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:kununu" {...props}></Icon>
