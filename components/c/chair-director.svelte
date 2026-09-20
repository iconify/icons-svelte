<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk3jmra7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dk3jmra7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chair-director" {...props}></Icon>
