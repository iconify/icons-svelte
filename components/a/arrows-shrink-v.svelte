<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v367-ccpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v367-ccpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:arrows-shrink-v" {...props}></Icon>
