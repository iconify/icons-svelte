<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edcg1xozq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edcg1xozq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:circle" {...props}></Icon>
