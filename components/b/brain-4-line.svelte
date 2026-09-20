<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4n3vub7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b4n3vub7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:brain-4-line" {...props}></Icon>
