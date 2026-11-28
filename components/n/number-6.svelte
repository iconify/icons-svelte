<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1m9ccbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1m9ccbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:number-6" {...props}></Icon>
