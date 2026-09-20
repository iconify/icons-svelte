<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgdbr_pqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="hgdbr_pqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:expand" {...props}></Icon>
