<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_yowkbgo.css';
import '../../css/l/lgdstuzsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c_yowkbgo"/><path class="lgdstuzsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:binder-48-bold" {...props}></Icon>
