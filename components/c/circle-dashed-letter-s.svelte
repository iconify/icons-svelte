<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lll22mbrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lll22mbrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dashed-letter-s" {...props}></Icon>
