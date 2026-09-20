<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-1l42bpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b-1l42bpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:peer-calls-light" {...props}></Icon>
