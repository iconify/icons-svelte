<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd6y7dbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pd6y7dbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:rabbit-filled" {...props}></Icon>
