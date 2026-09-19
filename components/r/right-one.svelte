<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix3m37btg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ix3m37btg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:right-one" {...props}></Icon>
