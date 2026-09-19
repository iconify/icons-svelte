<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alseh7nqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="alseh7nqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:bar-chart-alt" {...props}></Icon>
