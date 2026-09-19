<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l965g8jzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l965g8jzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:options-fill" {...props}></Icon>
