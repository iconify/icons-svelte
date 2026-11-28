<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwrrb6bqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwrrb6bqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:id-card-search" {...props}></Icon>
