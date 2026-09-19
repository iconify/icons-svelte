<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw-acp7gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nw-acp7gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:list-ol" {...props}></Icon>
