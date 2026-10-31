<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/h/h8fn3ebqz.css';
import '../../css/a/a5av5abdy.css';
import '../../css/h/hpztoy_nb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="h8fn3ebqz wm-shadow"/><path class="a5av5abdy wm-shadow"/><path class="hpztoy_nb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:repeat" {...props}></Icon>
