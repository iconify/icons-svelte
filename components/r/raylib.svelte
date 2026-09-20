<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op73mw-dx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="op73mw-dx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:raylib" {...props}></Icon>
