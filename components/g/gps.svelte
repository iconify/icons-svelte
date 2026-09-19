<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/j/j_h_6urrp.css';
import '../../css/v/vrh7e1bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="wwvp95byt"><path clip-rule="evenodd" class="j_h_6urrp"/><path class="vrh7e1bax"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:gps" {...props}></Icon>
