<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hch_afbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hch_afbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:folder-minus" {...props}></Icon>
