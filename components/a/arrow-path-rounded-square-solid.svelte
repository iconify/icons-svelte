<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h39unjboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h39unjboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-path-rounded-square-solid" {...props}></Icon>
