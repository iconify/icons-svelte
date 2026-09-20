<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4cnmn_xu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVG2Ib8ObKe" class="h4cnmn_xu"/></defs><use href="#SVG2Ib8ObKe"/><use href="#SVG2Ib8ObKe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:proteo" {...props}></Icon>
