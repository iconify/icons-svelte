<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd7ki4cpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rd7ki4cpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:door-closed-package" {...props}></Icon>
