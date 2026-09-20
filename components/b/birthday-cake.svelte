<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtoo5n7pl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gtoo5n7pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:birthday-cake" {...props}></Icon>
