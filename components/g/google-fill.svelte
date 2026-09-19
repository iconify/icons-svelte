<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro2maubeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ro2maubeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:google-fill" {...props}></Icon>
