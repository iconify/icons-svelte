<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go04vzgue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="go04vzgue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:hammer-and-anvil" {...props}></Icon>
