<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf-nwvhgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nf-nwvhgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:dock-window" {...props}></Icon>
