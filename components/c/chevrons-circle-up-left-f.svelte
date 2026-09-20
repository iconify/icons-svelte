<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kldt0jb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="kldt0jb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevrons-circle-up-left-f" {...props}></Icon>
