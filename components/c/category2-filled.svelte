<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9dmlwb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9dmlwb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:category2-filled" {...props}></Icon>
