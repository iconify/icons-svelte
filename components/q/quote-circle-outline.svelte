<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/i/il1hlbcqz.css';
import '../../css/g/g8ko324ru.css';
import '../../css/n/nwp387s1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="il1hlbcqz"/><path class="g8ko324ru"/><path class="nwp387s1b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:quote-circle-outline" {...props}></Icon>
