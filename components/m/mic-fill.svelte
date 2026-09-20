<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unvuw1rfu.css';
import '../../css/m/mkvymd0ml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="unvuw1rfu"/><path class="mkvymd0ml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:mic-fill" {...props}></Icon>
