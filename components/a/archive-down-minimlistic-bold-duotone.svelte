<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znv89pbeu.css';
import '../../css/p/pr6n6u_6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znv89pbeu"/><path clip-rule="evenodd" class="pr6n6u_6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-down-minimlistic-bold-duotone" {...props}></Icon>
