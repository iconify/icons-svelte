<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7qajsb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7qajsb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-48-small" {...props}></Icon>
