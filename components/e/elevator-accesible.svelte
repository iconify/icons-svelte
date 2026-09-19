<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6-qmrb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6-qmrb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:elevator-accesible" {...props}></Icon>
