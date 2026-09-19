<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_2j5obsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_2j5obsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lg-fridge" {...props}></Icon>
