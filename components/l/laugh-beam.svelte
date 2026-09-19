<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk4jnibns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="uk4jnibns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:laugh-beam" {...props}></Icon>
