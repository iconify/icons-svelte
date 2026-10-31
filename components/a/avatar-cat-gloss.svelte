<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9cdm0b2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9cdm0b2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-cat-gloss" {...props}></Icon>
