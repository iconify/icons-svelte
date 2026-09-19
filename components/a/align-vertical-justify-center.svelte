<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpa-aachc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpa-aachc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-vertical-justify-center" {...props}></Icon>
