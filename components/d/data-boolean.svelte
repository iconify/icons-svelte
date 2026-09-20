<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox9ffzb9n.css';
import '../../css/o/otxlapboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ox9ffzb9n"/><path class="otxlapboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:data-boolean" {...props}></Icon>
