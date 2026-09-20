<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6-5sk_bz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w6-5sk_bz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:arrow-diagonal-2-solid" {...props}></Icon>
