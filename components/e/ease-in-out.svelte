<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6z0rhxtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6z0rhxtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:ease-in-out" {...props}></Icon>
