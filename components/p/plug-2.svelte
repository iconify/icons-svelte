<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocgb-bj4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocgb-bj4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:plug-2" {...props}></Icon>
