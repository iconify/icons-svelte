<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgjmc8bpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgjmc8bpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nrwl" {...props}></Icon>
