<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3ma-5imm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3ma-5imm primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-big-up-duotone" {...props}></Icon>
