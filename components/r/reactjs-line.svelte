<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ognmpml1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ognmpml1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:reactjs-line" {...props}></Icon>
