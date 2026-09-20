<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glv3o6b_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="glv3o6b_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pray-fill" {...props}></Icon>
