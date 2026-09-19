<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dec5qrb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dec5qrb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:medium-fill" {...props}></Icon>
