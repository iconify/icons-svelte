<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbt3_ecay.css';
import '../../css/a/awy61ibgu.css';
import '../../css/y/yln89_oby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":331.399};
const content = `<path clip-rule="evenodd" class="mbt3_ecay"/><path clip-rule="evenodd" class="awy61ibgu"/><path clip-rule="evenodd" class="yln89_oby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:eps" {...props}></Icon>
