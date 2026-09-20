<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe09hgbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xe09hgbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:giv" {...props}></Icon>
