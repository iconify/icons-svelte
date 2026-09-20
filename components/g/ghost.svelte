<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4hg11bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4hg11bwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:ghost" {...props}></Icon>
