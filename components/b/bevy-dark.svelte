<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zdw9dcb7o.css';
import '../../css/m/mv06jzbvx.css';
import '../../css/i/i2wby7b4z.css';
import '../../css/h/hcp85kb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="zdw9dcb7o"/><path class="mv06jzbvx"/><path class="i2wby7b4z"/><path class="hcp85kb8d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="skill-icons:bevy-dark" {...props}></Icon>
