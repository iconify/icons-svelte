<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug-lo7bxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ug-lo7bxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:number-9-solid" {...props}></Icon>
