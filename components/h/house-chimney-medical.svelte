<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3m213b-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="t3m213b-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:house-chimney-medical" {...props}></Icon>
