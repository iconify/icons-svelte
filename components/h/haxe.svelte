<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrx6w39zp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrx6w39zp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:haxe" {...props}></Icon>
