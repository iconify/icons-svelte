<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc3sa0i4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rc3sa0i4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:penpot-light" {...props}></Icon>
