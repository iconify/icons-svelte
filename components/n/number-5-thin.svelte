<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac91_xbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ac91_xbdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-5-thin" {...props}></Icon>
