<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nar4fkb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nar4fkb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:align-left-two" {...props}></Icon>
