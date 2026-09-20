<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owbur9o1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owbur9o1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:el" {...props}></Icon>
