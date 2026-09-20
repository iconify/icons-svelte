<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1rizobub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w1rizobub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apache-answer" {...props}></Icon>
