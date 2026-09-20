<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jawpx2m9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jawpx2m9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-x-fill" {...props}></Icon>
