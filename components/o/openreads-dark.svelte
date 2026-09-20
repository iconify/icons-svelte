<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk3kyxb9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fk3kyxb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openreads-dark" {...props}></Icon>
