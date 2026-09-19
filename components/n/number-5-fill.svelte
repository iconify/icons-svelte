<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-rr4qaar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f-rr4qaar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-5-fill" {...props}></Icon>
