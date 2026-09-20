<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqdgb1rqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqdgb1rqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hand-right" {...props}></Icon>
