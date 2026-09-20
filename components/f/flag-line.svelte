<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hoca2wvbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hoca2wvbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:flag-line" {...props}></Icon>
