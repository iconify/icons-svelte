<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eomj11bqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eomj11bqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:intelowl-light" {...props}></Icon>
