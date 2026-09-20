<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkz3ovj8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zkz3ovj8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:firewall-flame" {...props}></Icon>
