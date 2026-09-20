<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d50imbb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d50imbb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openrouter" {...props}></Icon>
