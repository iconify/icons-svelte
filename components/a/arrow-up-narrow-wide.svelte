<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfbxiibek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfbxiibek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-up-narrow-wide" {...props}></Icon>
