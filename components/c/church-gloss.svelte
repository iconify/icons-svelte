<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd7wx3zmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd7wx3zmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:church-gloss" {...props}></Icon>
