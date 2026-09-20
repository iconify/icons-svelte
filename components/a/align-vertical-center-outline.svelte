<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfj16fbzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jfj16fbzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-vertical-center-outline" {...props}></Icon>
