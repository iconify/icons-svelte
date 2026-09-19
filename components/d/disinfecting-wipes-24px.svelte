<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arbx19las.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="arbx19las"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:disinfecting-wipes-24px" {...props}></Icon>
