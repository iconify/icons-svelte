<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyeq4tbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyeq4tbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:alphabet-devanagari" {...props}></Icon>
