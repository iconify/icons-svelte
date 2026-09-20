<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe5ax8ult.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qe5ax8ult"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:droplet-code" {...props}></Icon>
