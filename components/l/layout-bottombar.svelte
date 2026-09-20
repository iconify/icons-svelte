<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iduzk8jau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iduzk8jau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-bottombar" {...props}></Icon>
