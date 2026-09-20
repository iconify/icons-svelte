<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncg6fst_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncg6fst_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-in-right-dashed-panel-fill" {...props}></Icon>
