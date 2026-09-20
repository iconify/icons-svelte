<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du2e67bis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="du2e67bis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-right-line" {...props}></Icon>
