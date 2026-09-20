<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pksxh-eye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pksxh-eye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:chevron-up-solid" {...props}></Icon>
