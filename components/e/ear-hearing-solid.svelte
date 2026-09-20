<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waci2fbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="waci2fbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ear-hearing-solid" {...props}></Icon>
