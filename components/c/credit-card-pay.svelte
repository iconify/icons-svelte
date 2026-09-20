<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7a949o5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7a949o5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:credit-card-pay" {...props}></Icon>
