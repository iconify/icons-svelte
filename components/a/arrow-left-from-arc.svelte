<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcymdsb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tcymdsb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-left-from-arc" {...props}></Icon>
