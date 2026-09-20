<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk6a7rbpz.css';
import '../../css/y/ya8a87bqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sk6a7rbpz"/><path class="ya8a87bqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:reflect-down-bold" {...props}></Icon>
