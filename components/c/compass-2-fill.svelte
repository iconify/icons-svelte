<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmqj6vz6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pmqj6vz6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:compass-2-fill" {...props}></Icon>
