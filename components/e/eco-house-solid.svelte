<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2nilsb3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j2nilsb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:eco-house-solid" {...props}></Icon>
