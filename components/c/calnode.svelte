<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/daxysxbef.css';
import '../../css/y/y0oobqogr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="daxysxbef"/><path class="y0oobqogr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:calnode" {...props}></Icon>
