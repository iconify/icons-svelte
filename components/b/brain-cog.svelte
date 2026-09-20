<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6q2pl6bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6q2pl6bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:brain-cog" {...props}></Icon>
