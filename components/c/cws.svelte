<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtlmueb0q.css';
import '../../css/f/fckebnbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtlmueb0q"/><path clip-rule="evenodd" class="fckebnbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cws" {...props}></Icon>
