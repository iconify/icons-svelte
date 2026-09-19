<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhzvn0bxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhzvn0bxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:paragraph-outline" {...props}></Icon>
