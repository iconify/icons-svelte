<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp6xqgbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bp6xqgbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kohls-dark" {...props}></Icon>
