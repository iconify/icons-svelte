<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue7a0iekt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue7a0iekt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:envelope-info" {...props}></Icon>
