<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oakaq48zu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oakaq48zu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-5-circle-fill" {...props}></Icon>
