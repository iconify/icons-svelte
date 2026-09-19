<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adh6zfbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adh6zfbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:google-outline" {...props}></Icon>
