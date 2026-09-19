<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ors6mho2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ors6mho2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:filter" {...props}></Icon>
