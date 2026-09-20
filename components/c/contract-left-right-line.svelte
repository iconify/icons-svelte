<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma25g4b2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ma25g4b2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:contract-left-right-line" {...props}></Icon>
