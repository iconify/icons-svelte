<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfywpjbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yfywpjbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:battry-half-solid" {...props}></Icon>
