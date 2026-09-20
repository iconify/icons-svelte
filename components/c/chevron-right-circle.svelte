<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4ajofb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="y4ajofb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:chevron-right-circle" {...props}></Icon>
