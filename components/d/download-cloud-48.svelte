<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3ugn4t5k.css';
import '../../css/o/odh7t-j9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g3ugn4t5k"/><path class="odh7t-j9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:download-cloud-48" {...props}></Icon>
