<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbaq2ia5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bbaq2ia5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:forms" {...props}></Icon>
