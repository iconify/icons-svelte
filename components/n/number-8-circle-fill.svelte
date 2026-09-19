<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onmpbbb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="onmpbbb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-8-circle-fill" {...props}></Icon>
