<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn6wamb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sn6wamb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:link" {...props}></Icon>
