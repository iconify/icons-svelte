<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv-8_vb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lv-8_vb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:firefly-adobe" {...props}></Icon>
