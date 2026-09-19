<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcgdaipoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcgdaipoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:clipboard-list-filled" {...props}></Icon>
