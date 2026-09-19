<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx0y_snju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qx0y_snju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:rewind" {...props}></Icon>
