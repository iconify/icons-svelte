<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rinuwhlnp.css';
import '../../css/f/f1b8dob7c.css';
import '../../css/y/y06nxiblq.css';
import '../../css/h/hng779tvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="rinuwhlnp"><rect class="f1b8dob7c"/><rect class="y06nxiblq"/><rect class="hng779tvz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:align-vertical-center-two" {...props}></Icon>
