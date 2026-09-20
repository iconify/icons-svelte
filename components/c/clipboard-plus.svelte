<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lehcu0c0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lehcu0c0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:clipboard-plus" {...props}></Icon>
