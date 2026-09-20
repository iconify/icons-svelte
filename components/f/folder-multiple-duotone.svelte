<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh404cczq.css';
import '../../css/p/p343mol7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wh404cczq"/><path clip-rule="evenodd" class="p343mol7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-multiple-duotone" {...props}></Icon>
