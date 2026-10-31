<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu9u27bcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu9u27bcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cow-round" {...props}></Icon>
