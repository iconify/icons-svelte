<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veuw6sb6b.css';
import '../../css/e/ekcp3cc9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="veuw6sb6b"/><path class="ekcp3cc9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cdt" {...props}></Icon>
