<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq7-5m55k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wq7-5m55k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:castle-fill" {...props}></Icon>
