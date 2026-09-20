<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5s8cwpbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n5s8cwpbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:lock-2" {...props}></Icon>
