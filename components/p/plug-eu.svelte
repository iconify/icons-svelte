<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yaf099rbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yaf099rbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:plug-eu" {...props}></Icon>
