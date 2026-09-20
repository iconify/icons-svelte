<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwe1oubqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwe1oubqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:codestream" {...props}></Icon>
