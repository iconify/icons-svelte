<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4s1fkb8q.css';
import '../../css/u/ua9aj-d3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v4s1fkb8q"/><path class="ua9aj-d3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openadserver-dark" {...props}></Icon>
