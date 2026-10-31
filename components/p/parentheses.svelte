<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/n/nd8oncbxa.css';
import '../../css/y/yailk0b5w.css';
import '../../css/m/mv53-jfge.css';
import '../../css/d/d8fckhbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="nd8oncbxa wm-shadow"/><path class="wm-shadow yailk0b5w"/><path class="mv53-jfge"/><path class="d8fckhbji"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:parentheses" {...props}></Icon>
