<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvbs_bbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvbs_bbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:blazor" {...props}></Icon>
