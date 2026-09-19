<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grla34_uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grla34_uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:folder" {...props}></Icon>
