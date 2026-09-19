<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdehhlppr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdehhlppr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:code-bracket-square" {...props}></Icon>
