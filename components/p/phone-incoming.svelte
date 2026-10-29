<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9xv9fbxk.css';
import '../../css/o/o62a0f6-k.css';
import '../../css/s/s9-kjp2aw.css';
import '../../css/c/cahwctb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9xv9fbxk wm-k"/><path class="o62a0f6-k wm-k"/><path class="s9-kjp2aw wm-s"/><path class="cahwctb7b wm-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:phone-incoming" {...props}></Icon>
