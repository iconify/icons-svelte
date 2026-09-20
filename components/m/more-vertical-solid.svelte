<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uik8bmg6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="uik8bmg6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:more-vertical-solid" {...props}></Icon>
