<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytmtt4p6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ytmtt4p6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:baseball-bat-ball" {...props}></Icon>
