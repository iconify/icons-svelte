<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p49jc6i4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p49jc6i4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:loom" {...props}></Icon>
