<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u09qkpbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-6,"top":-6.5};
const content = `<path class="u09qkpbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:arrow-up-left" {...props}></Icon>
