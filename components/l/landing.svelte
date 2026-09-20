<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjr1hxbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fjr1hxbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:landing" {...props}></Icon>
