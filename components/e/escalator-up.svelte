<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8r6v-bvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8r6v-bvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:escalator-up" {...props}></Icon>
