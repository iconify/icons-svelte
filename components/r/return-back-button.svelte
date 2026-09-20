<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efpwwnbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="efpwwnbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:return-back-button" {...props}></Icon>
