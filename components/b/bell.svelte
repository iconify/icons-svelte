<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm834cbqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jm834cbqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:bell" {...props}></Icon>
