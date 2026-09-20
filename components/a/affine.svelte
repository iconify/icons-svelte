<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2o9v4b6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2o9v4b6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:affine" {...props}></Icon>
