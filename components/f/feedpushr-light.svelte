<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/covpzf56i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="covpzf56i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:feedpushr-light" {...props}></Icon>
