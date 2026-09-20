<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7fn06bpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c7fn06bpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:animal-planet" {...props}></Icon>
