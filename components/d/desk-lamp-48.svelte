<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sabjbxbkn.css';
import '../../css/k/kosmuobvp.css';
import '../../css/i/iln-rgb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sabjbxbkn"/><path class="kosmuobvp"/><path class="iln-rgb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:desk-lamp-48" {...props}></Icon>
