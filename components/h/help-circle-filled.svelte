<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6a7u-sfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6a7u-sfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:help-circle-filled" {...props}></Icon>
