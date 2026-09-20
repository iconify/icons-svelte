<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq8ti6bee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="jq8ti6bee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevrons-circle-down-left" {...props}></Icon>
