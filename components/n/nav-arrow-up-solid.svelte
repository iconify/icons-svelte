<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hln_84bad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hln_84bad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:nav-arrow-up-solid" {...props}></Icon>
