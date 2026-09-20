<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bybb08b1e.css';
import '../../css/i/ignl7ccte.css';
import '../../css/o/os13rubjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bybb08b1e"/><path class="ignl7ccte"/><path class="os13rubjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:data-file-bars-add-bold" {...props}></Icon>
