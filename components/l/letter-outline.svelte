<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf42xuuot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rf42xuuot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:letter-outline" {...props}></Icon>
