<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn2xogvfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pn2xogvfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:face-neutral-round" {...props}></Icon>
