<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggrgy84wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ggrgy84wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:road-circle-xmark" {...props}></Icon>
