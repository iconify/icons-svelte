<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbej7n56x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wbej7n56x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-7-square-fill" {...props}></Icon>
