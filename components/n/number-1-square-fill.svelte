<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7cj1lbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o7cj1lbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-1-square-fill" {...props}></Icon>
