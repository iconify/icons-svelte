<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyhe6ac1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyhe6ac1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-4-small" {...props}></Icon>
