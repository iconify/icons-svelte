<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm7_4jbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bm7_4jbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:brush" {...props}></Icon>
