<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fezzo6f2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="fezzo6f2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cat" {...props}></Icon>
