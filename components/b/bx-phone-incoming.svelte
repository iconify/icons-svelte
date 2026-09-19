<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qryyscb4x.css';
import '../../css/s/siitcdcqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qryyscb4x"/><path class="siitcdcqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-phone-incoming" {...props}></Icon>
