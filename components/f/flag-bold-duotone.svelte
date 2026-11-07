<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq6b85b-a.css';
import '../../css/w/wz-8q9ofo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cq6b85b-a"/><path class="wz-8q9ofo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:flag-bold-duotone" {...props}></Icon>
