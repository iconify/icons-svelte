<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itaejdbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itaejdbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:link-up" {...props}></Icon>
