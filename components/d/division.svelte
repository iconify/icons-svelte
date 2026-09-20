<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf7y1jtyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="sf7y1jtyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:division" {...props}></Icon>
