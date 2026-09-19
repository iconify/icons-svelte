<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/i/i850pr6dl.css';
import '../../css/a/af6587_nt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="i850pr6dl"/><path class="af6587_nt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:error-reporting" {...props}></Icon>
