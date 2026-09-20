<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k29omfbdq.css';
import '../../css/v/v0quseb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k29omfbdq"/><path clip-rule="evenodd" class="v0quseb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:ellipsis-v-duotone" {...props}></Icon>
