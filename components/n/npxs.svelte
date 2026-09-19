<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ip-c2mbtb.css';
import '../../css/m/md286fbip.css';
import '../../css/q/qt4d1naee.css';
import '../../css/h/hvd63zboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="ip-c2mbtb"/><g class="md286fbip"><path class="qt4d1naee"/><path class="hvd63zboa"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:npxs" {...props}></Icon>
