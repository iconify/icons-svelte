<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9tegybcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i9tegybcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:id-card-alt" {...props}></Icon>
