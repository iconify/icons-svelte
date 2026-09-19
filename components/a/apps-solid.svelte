<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kopogg_hi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kopogg_hi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:apps-solid" {...props}></Icon>
