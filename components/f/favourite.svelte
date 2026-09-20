<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_8vpzbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="e_8vpzbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:favourite" {...props}></Icon>
