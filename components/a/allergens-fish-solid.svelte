<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp2qlwbgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yp2qlwbgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:allergens-fish-solid" {...props}></Icon>
