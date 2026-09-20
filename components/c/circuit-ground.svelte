<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev03z9c2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ev03z9c2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circuit-ground" {...props}></Icon>
