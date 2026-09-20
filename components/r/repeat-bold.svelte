<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htre3kb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="htre3kb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:repeat-bold" {...props}></Icon>
