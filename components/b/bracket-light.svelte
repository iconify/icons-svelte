<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfamlxbej.css';
import '../../css/l/lwt7zu3on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dfamlxbej"/><path class="lwt7zu3on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bracket-light" {...props}></Icon>
