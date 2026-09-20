<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_gde_yhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_gde_yhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:money-cny-box-line" {...props}></Icon>
