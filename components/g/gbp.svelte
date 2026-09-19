<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i335q_--m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":24};
const content = `<path class="i335q_--m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:gbp" {...props}></Icon>
