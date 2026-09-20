<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/one-8ebop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="one-8ebop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:flag-cog" {...props}></Icon>
