<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgnxkc84e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="mgnxkc84e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:file-php-fill" {...props}></Icon>
