<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9vaa1ezk.css';
import '../../css/n/nidir5bxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b9vaa1ezk"/><path class="nidir5bxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-bell" {...props}></Icon>
