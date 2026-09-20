<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p24ypjbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p24ypjbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circles-filled" {...props}></Icon>
