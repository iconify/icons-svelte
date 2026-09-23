<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/w/wqf_9i70w.css';
import '../../css/b/b5d7f1b7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><rect class="wqf_9i70w"/><path class="b5d7f1b7l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:gamepad" {...props}></Icon>
