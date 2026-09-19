<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otbfd4iee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otbfd4iee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:panel-left-dashed" {...props}></Icon>
