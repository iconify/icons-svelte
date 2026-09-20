<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i25hxerjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i25hxerjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dashed-number-6" {...props}></Icon>
