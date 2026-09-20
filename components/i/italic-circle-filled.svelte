<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_-c2-bmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y_-c2-bmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:italic-circle-filled" {...props}></Icon>
