<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9uir488u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9uir488u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:cc-solid" {...props}></Icon>
