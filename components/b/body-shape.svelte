<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7mu9cjrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y7mu9cjrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:body-shape" {...props}></Icon>
