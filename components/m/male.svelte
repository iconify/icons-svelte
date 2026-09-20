<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf04q1bge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kf04q1bge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:male" {...props}></Icon>
