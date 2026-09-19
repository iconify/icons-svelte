<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3c725ova.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="x3c725ova"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:person-crop-circle-badge-exclam" {...props}></Icon>
