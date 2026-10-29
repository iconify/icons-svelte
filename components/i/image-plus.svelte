<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4oqcxbpe.css';
import '../../css/e/egyqx8bap.css';
import '../../css/i/iwfcdhl5u.css';
import '../../css/q/qicp8db8o.css';
import '../../css/v/vqrvagbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4oqcxbpe wm-k"/><path class="egyqx8bap wm-a"/><path class="iwfcdhl5u wm-k"/><path class="qicp8db8o wm-s"/><path class="vqrvagbdq wm-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:image-plus" {...props}></Icon>
