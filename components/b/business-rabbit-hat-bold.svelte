<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha_mr3xlv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ha_mr3xlv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:business-rabbit-hat-bold" {...props}></Icon>
