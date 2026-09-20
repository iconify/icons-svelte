<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no308zbzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="no308zbzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:paperclip-2" {...props}></Icon>
