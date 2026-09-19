<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1t73q-cv.css';
import '../../css/k/kisx4ib0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1t73q-cv duoicon-secondary-layer"/><path class="duoicon-primary-layer kisx4ib0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:baby-carriage" {...props}></Icon>
