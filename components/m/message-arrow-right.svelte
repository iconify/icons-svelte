<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-pp4uinw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-pp4uinw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:message-arrow-right" {...props}></Icon>
