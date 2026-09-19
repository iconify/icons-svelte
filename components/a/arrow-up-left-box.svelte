<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftz4bxa2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ftz4bxa2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-up-left-box" {...props}></Icon>
