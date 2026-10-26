<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsg68bc0n.css';
import '../../css/b/bv7go7mgj.css';
import '../../css/o/o5biosboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="qsg68bc0n"><path class="bv7go7mgj"/><path class="o5biosboo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:news" {...props}></Icon>
