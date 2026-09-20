<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9z7u7b7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9z7u7b7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:forward-sharp-fill" {...props}></Icon>
