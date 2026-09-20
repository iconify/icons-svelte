<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj9fenb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj9fenb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:natsdotio" {...props}></Icon>
