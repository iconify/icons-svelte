<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-97j2bib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="k-97j2bib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:halberd" {...props}></Icon>
