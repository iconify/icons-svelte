<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tst_x0jpw.css';
import '../../css/t/twmjonw6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tst_x0jpw"/><path clip-rule="evenodd" class="twmjonw6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:image-play-filled" {...props}></Icon>
