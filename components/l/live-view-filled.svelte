<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1clq8fia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1clq8fia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:live-view-filled" {...props}></Icon>
