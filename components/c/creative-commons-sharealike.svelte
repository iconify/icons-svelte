<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvyl42ogw.css';
import '../../css/l/l252cwxrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="mvyl42ogw"/><path class="l252cwxrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:creative-commons-sharealike" {...props}></Icon>
