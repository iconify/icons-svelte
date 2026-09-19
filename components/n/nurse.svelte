<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbcopub7q.css';
import '../../css/b/b1n3f83cw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":24};
const content = `<path class="xbcopub7q"/><path class="b1n3f83cw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:nurse" {...props}></Icon>
