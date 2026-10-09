<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j174--bix.css';
import '../../css/y/y9e_r21yc.css';
import '../../css/f/fd0w32b9p.css';
import '../../css/o/oqrsy3bng.css';
import '../../css/b/bqy7-kv9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j174--bix"/><path class="y9e_r21yc"/><path class="fd0w32b9p"/><path class="oqrsy3bng"/><path class="bqy7-kv9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plug-x-48-bold" {...props}></Icon>
