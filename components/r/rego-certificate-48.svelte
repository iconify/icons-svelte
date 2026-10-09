<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuvdc2bma.css';
import '../../css/u/u04sb4b-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yuvdc2bma"/><path class="u04sb4b-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rego-certificate-48" {...props}></Icon>
