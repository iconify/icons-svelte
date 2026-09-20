<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2la8ubsr.css';
import '../../css/r/rphcwab-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2la8ubsr"/><path class="rphcwab-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-edit-filled" {...props}></Icon>
