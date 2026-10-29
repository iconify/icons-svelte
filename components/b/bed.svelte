<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7p__wdjy.css';
import '../../css/d/df84tibzk.css';
import '../../css/g/gm3lalblg.css';
import '../../css/o/ousiqgb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7p__wdjy"/><path class="df84tibzk"/><path class="gm3lalblg"/><path class="ousiqgb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:bed" {...props}></Icon>
