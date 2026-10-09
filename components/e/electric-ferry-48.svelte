<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbryxcakh.css';
import '../../css/v/ven9i71ui.css';
import '../../css/c/cvs64bbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dbryxcakh"/><path class="ven9i71ui"/><path class="cvs64bbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-ferry-48" {...props}></Icon>
