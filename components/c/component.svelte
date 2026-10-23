<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djb7u20ie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djb7u20ie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:component" {...props}></Icon>
