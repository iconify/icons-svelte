<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxcp3cjpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxcp3cjpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fast-forward-line" {...props}></Icon>
