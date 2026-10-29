<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h28_f0buv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h28_f0buv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:folder" {...props}></Icon>
