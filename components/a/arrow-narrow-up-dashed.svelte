<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igrvd-boo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="igrvd-boo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-narrow-up-dashed" {...props}></Icon>
