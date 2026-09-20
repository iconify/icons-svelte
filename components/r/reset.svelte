<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1nqbh-cb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l1nqbh-cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:reset" {...props}></Icon>
