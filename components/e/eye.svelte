<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzv0rab7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzv0rab7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:eye" {...props}></Icon>
