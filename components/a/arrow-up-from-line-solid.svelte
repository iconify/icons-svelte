<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjc6lacrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjc6lacrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-up-from-line-solid" {...props}></Icon>
