<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfmy84bkp.css';
import '../../css/r/rgmiyo8xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pfmy84bkp"/><path class="rgmiyo8xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chef-knife-48-bold" {...props}></Icon>
