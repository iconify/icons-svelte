<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulw3jib_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulw3jib_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:de-longhi" {...props}></Icon>
