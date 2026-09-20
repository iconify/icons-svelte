<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqo7-v_cz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vqo7-v_cz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cart2" {...props}></Icon>
