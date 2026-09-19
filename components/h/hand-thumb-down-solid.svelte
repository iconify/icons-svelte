<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/febe2bc5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="febe2bc5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:hand-thumb-down-solid" {...props}></Icon>
