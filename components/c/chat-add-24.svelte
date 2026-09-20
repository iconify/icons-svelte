<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkvpl8bch.css';
import '../../css/j/j6h96-z2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dkvpl8bch"/><path class="j6h96-z2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:chat-add-24" {...props}></Icon>
