<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpl68-y4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lpl68-y4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:maximize-square-2-bold" {...props}></Icon>
