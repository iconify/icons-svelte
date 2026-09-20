<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vebss22ta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vebss22ta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:maserati" {...props}></Icon>
