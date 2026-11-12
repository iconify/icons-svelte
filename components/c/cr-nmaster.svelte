<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2dqk2sur.css';
import '../../css/r/rb6k0dd7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g2dqk2sur"/><path class="rb6k0dd7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cr-nmaster" {...props}></Icon>
