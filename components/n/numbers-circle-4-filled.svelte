<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwrybibvp.css';
import '../../css/h/hf_2iyb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwrybibvp"/><path class="hf_2iyb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:numbers-circle-4-filled" {...props}></Icon>
