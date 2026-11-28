<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb-vml4nv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lb-vml4nv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-up-square-solid" {...props}></Icon>
