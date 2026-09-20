<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7658vijs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="i7658vijs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:hashtag-solid" {...props}></Icon>
