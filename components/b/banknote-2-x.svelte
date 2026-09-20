<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wylrpqbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wylrpqbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:banknote-2-x" {...props}></Icon>
