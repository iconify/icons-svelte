<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i04yw6bfv.css';
import '../../css/i/ifilulb6g.css';
import '../../css/b/b1ecs5fbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="i04yw6bfv"/><path class="ifilulb6g"/><path class="b1ecs5fbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-credit-card-alt" {...props}></Icon>
