<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqmw9v60f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqmw9v60f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:franprix" {...props}></Icon>
