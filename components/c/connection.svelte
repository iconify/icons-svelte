<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6-_72oka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6-_72oka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:connection" {...props}></Icon>
