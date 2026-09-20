<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cch0s05jp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cch0s05jp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:image-highlights-remix" {...props}></Icon>
