<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apqzseb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="apqzseb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:capsule-1" {...props}></Icon>
