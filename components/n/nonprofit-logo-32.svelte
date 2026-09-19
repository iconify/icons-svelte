<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if8gqlbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="if8gqlbdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:nonprofit-logo-32" {...props}></Icon>
