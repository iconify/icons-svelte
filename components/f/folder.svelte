<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql0_h4g3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ql0_h4g3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:folder" {...props}></Icon>
