<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw9z6cbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kw9z6cbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:backblaze-dark" {...props}></Icon>
