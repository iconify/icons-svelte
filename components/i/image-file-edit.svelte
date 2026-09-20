<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/futw48ihu.css';
import '../../css/s/sngyf7baf.css';
import '../../css/l/lg55wobni.css';
import '../../css/a/apeazccje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="futw48ihu"/><path class="sngyf7baf"/><path class="lg55wobni"/><path class="apeazccje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:image-file-edit" {...props}></Icon>
