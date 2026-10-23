<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe43_rbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qe43_rbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:pill-bottle" {...props}></Icon>
