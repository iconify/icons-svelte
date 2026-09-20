<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geaowwqpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="geaowwqpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:discuss-fill" {...props}></Icon>
