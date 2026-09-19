<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo4ka8j4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yo4ka8j4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:lasso" {...props}></Icon>
