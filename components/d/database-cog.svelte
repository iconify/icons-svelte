<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnry6fbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnry6fbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:database-cog" {...props}></Icon>
