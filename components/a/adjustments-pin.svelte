<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlhw53boa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rlhw53boa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:adjustments-pin" {...props}></Icon>
