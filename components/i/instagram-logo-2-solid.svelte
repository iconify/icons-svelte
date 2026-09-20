<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzk1px2nz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hzk1px2nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:instagram-logo-2-solid" {...props}></Icon>
