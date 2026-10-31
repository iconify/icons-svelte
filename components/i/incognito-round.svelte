<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/begkzfwcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="begkzfwcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:incognito-round" {...props}></Icon>
