<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r15cen0uv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r15cen0uv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-down-circle-solid" {...props}></Icon>
