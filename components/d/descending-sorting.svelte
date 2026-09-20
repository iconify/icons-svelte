<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hna-dab_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hna-dab_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:descending-sorting" {...props}></Icon>
