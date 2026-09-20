<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-pyqox9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c-pyqox9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dev-push-light" {...props}></Icon>
