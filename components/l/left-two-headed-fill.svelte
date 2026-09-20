<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izyf8vb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izyf8vb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:left-two-headed-fill" {...props}></Icon>
