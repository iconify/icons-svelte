<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvlwphb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvlwphb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:number-8" {...props}></Icon>
