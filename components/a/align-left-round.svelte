<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whde9goyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whde9goyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:align-left-round" {...props}></Icon>
