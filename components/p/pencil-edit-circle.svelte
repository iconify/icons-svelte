<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijywvtboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijywvtboo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pencil-edit-circle" {...props}></Icon>
