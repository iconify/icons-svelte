<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-r527bwo.css';
import '../../css/s/s222euk2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b-r527bwo"/><path class="s222euk2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nezha-dark" {...props}></Icon>
