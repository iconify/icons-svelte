<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppuvh0l0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="ppuvh0l0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:charge-battery" {...props}></Icon>
