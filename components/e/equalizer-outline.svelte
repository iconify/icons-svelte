<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhssxcbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhssxcbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:equalizer-outline" {...props}></Icon>
