<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9gb9bbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v9gb9bbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:double-take-light" {...props}></Icon>
