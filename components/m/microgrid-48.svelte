<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1iv3qhdn.css';
import '../../css/d/de1hnzbwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d1iv3qhdn"/><path class="de1hnzbwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:microgrid-48" {...props}></Icon>
