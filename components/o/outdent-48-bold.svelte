<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo6zpuchv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mo6zpuchv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:outdent-48-bold" {...props}></Icon>
