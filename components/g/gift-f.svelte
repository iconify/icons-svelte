<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc70u4buk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="vc70u4buk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:gift-f" {...props}></Icon>
