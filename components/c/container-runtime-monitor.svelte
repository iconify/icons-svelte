<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3vxumw8s.css';
import '../../css/g/gkjqfnbjw.css';
import '../../css/g/g7isto0zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="v3vxumw8s"/><path class="gkjqfnbjw"/><path class="g7isto0zn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:container-runtime-monitor" {...props}></Icon>
