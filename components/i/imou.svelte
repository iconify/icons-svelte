<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b79w96bqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b79w96bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:imou" {...props}></Icon>
