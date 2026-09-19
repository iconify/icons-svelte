<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b68poibwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b68poibwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:recording-fill" {...props}></Icon>
