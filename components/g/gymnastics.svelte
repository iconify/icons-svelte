<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j__y33b5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j__y33b5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:gymnastics" {...props}></Icon>
