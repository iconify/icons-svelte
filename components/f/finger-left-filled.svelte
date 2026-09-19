<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9wwu21rw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9wwu21rw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:finger-left-filled" {...props}></Icon>
