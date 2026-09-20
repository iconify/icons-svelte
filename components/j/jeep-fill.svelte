<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgd-5o5ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dgd-5o5ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:jeep-fill" {...props}></Icon>
