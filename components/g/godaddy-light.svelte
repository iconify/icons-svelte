<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqqsz-bhg.css';
import '../../css/j/j_opgppca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":166,"height":34};
const content = `<path class="pqqsz-bhg prefix__path-mobile"/><path class="j_opgppca prefix__path-desktop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:godaddy-light" {...props}></Icon>
