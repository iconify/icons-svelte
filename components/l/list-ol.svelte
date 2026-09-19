<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb2thqbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kb2thqbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:list-ol" {...props}></Icon>
