<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krtu8nbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krtu8nbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrows-double-nw-se" {...props}></Icon>
