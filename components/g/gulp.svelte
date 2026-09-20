<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnl55nosd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gnl55nosd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:gulp" {...props}></Icon>
