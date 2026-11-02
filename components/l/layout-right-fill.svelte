<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbc_5ab7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbc_5ab7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-right-fill" {...props}></Icon>
