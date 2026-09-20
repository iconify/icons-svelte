<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/noigyud1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="noigyud1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:qui-dark" {...props}></Icon>
