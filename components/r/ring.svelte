<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsg68bc0n.css';
import '../../css/i/iom06ubvw.css';
import '../../css/h/hocchnbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="qsg68bc0n"><path class="iom06ubvw"/><path class="hocchnbix"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:ring" {...props}></Icon>
