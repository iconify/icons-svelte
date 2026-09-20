<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1bv9444m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u1bv9444m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:laptop-project-screen-remix" {...props}></Icon>
