<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs08r5bpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="rs08r5bpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:double-caret-left-circle-solid" {...props}></Icon>
