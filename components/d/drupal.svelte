<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cllix0kul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":416,"height":488};
const content = `<path class="cllix0kul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:drupal" {...props}></Icon>
