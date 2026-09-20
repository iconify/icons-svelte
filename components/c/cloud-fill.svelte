<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztsfy6b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztsfy6b2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cloud-fill" {...props}></Icon>
