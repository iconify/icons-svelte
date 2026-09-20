<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl8cp6tgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gl8cp6tgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bookmark" {...props}></Icon>
