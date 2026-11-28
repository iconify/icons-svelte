<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaaagyarv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uaaagyarv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:number-7-duo" {...props}></Icon>
