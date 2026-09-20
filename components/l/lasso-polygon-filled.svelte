<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq_tio5rh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eq_tio5rh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:lasso-polygon-filled" {...props}></Icon>
