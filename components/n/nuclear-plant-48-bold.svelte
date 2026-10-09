<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo3rjpgxd.css';
import '../../css/d/dujsdbckk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yo3rjpgxd"/><path class="dujsdbckk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:nuclear-plant-48-bold" {...props}></Icon>
