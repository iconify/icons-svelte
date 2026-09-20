<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjig1n2-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjig1n2-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:persistent" {...props}></Icon>
