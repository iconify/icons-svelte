<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nznd92b3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nznd92b3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:divide" {...props}></Icon>
