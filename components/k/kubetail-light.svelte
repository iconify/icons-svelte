<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsr9job0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jsr9job0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kubetail-light" {...props}></Icon>
