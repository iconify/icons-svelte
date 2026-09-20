<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9cyzoooz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9cyzoooz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:logseq" {...props}></Icon>
