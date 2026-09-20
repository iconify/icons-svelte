<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9_j80bgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9_j80bgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:grapheneos" {...props}></Icon>
