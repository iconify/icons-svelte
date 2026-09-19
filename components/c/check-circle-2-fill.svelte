<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-0xj5x9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a-0xj5x9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:check-circle-2-fill" {...props}></Icon>
