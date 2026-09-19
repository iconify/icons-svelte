<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggt--tbja.css';
import '../../css/t/thqtvsbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggt--tbja"/><path clip-rule="evenodd" class="thqtvsbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:heart-off-outline" {...props}></Icon>
