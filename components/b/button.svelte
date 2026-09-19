<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c542o2ulc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c542o2ulc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:button" {...props}></Icon>
