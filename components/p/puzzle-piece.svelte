<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n204gnbbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n204gnbbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:puzzle-piece" {...props}></Icon>
