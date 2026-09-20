<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u37d7hbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u37d7hbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:personal-management-system-light" {...props}></Icon>
