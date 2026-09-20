<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eozj_aczo.css';
import '../../css/u/u5aprybjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eozj_aczo"/><path class="u5aprybjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:layers-bring-backward" {...props}></Icon>
