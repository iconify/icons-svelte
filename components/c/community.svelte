<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvo_y9b8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kvo_y9b8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:community" {...props}></Icon>
