<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpa4a0bsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpa4a0bsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-up-right-solid" {...props}></Icon>
