<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajm915b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="ajm915b5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:drum-steelpan" {...props}></Icon>
