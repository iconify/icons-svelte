<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beld5sdfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="beld5sdfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:ban-2" {...props}></Icon>
