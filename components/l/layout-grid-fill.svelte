<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0rxg3blc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0rxg3blc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:layout-grid-fill" {...props}></Icon>
