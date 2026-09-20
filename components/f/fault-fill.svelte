<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abrao85rm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="abrao85rm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fault-fill" {...props}></Icon>
