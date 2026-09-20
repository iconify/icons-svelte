<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksvy_1bhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksvy_1bhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:meizu" {...props}></Icon>
