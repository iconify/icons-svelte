<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8nx62r-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="g8nx62r-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:plant-solid" {...props}></Icon>
