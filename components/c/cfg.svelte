<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgf21yb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgf21yb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cfg" {...props}></Icon>
