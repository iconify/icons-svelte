<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc8ov__gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nc8ov__gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:grid" {...props}></Icon>
