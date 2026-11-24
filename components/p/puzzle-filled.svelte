<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2h02n6ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o2h02n6ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:puzzle-filled" {...props}></Icon>
