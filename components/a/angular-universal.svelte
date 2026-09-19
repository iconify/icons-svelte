<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnw5ewbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rnw5ewbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:angular-universal" {...props}></Icon>
