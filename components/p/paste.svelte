<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dspl9r1xw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dspl9r1xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:paste" {...props}></Icon>
