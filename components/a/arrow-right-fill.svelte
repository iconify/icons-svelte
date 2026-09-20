<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6lkrgb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6lkrgb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:arrow-right-fill" {...props}></Icon>
