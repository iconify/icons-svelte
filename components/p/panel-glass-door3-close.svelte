<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pioptztzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pioptztzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:panel-glass-door3-close" {...props}></Icon>
