<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrxlgg64z.css';
import '../../css/i/iu35e1xme.css';
import '../../css/w/wa-7pugao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="hrxlgg64z"/><circle class="iu35e1xme"/><path class="wa-7pugao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:exclamation-circle" {...props}></Icon>
