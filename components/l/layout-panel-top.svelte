<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcf4tjbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcf4tjbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:layout-panel-top" {...props}></Icon>
