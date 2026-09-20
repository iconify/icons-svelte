<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhu87ubnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhu87ubnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:pentagon-fill" {...props}></Icon>
