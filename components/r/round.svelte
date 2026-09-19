<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9v4wgnrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="h9v4wgnrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:round" {...props}></Icon>
