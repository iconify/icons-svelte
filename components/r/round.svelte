<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjei4k8qe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cjei4k8qe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:round" {...props}></Icon>
