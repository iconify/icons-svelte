<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgkj53bit.css';
import '../../css/o/o11kupslz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cgkj53bit"/><path class="o11kupslz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:play-circle-bold-duotone" {...props}></Icon>
