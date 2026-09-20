<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqieu0njm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-1.5,"top":-1.5};
const content = `<path class="aqieu0njm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:bandage" {...props}></Icon>
