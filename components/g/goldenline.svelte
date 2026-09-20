<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amdk3mbmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amdk3mbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:goldenline" {...props}></Icon>
