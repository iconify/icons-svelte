<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lob-de45c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lob-de45c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:letter-l-small" {...props}></Icon>
