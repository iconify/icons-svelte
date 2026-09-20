<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4jt-mads.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4jt-mads"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:lock-open-solid" {...props}></Icon>
