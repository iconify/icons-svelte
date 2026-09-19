<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt5xi-btt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xt5xi-btt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlearrowleft" {...props}></Icon>
