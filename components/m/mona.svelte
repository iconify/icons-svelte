<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td4-k_bre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="td4-k_bre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mona" {...props}></Icon>
