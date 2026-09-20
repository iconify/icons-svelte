<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv15p9qut.css';
import '../../css/t/tytb7gbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yv15p9qut"/><path class="tytb7gbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:inspect-fill" {...props}></Icon>
