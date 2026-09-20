<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts2d2vjbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ts2d2vjbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rainyun" {...props}></Icon>
