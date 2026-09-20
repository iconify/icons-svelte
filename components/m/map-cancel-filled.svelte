<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k52qndt3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k52qndt3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-cancel-filled" {...props}></Icon>
