<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vniww6bxz.css';
import '../../css/q/qtu4m29vr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vniww6bxz"/><path clip-rule="evenodd" class="qtu4m29vr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:palette-outline" {...props}></Icon>
