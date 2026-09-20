<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwj0sbclr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwj0sbclr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-88-small" {...props}></Icon>
