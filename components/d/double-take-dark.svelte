<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jht319lou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jht319lou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:double-take-dark" {...props}></Icon>
