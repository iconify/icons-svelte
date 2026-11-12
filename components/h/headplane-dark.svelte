<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b89dqjg6u.css';
import '../../css/h/h9o14dbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b89dqjg6u"/><path class="h9o14dbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:headplane-dark" {...props}></Icon>
