<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8_pm-bqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8_pm-bqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:number-4-solid" {...props}></Icon>
