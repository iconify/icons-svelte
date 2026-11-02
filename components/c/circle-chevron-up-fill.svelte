<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4qntxb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4qntxb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-chevron-up-fill" {...props}></Icon>
