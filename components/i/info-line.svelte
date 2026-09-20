<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovn9bfb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovn9bfb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:info-line" {...props}></Icon>
