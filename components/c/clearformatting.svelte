<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnp-6j6hh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lnp-6j6hh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:clearformatting" {...props}></Icon>
