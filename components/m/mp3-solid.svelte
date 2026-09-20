<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uql2cd25u.css';
import '../../css/l/l2fsr4bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uql2cd25u"/><path clip-rule="evenodd" class="l2fsr4bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:mp3-solid" {...props}></Icon>
