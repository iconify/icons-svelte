<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1ajybbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1ajybbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrows-left-fill" {...props}></Icon>
