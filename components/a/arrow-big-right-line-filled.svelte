<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkmq3hkqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nkmq3hkqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-big-right-line-filled" {...props}></Icon>
