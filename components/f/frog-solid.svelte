<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z24l2abjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z24l2abjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:frog-solid" {...props}></Icon>
