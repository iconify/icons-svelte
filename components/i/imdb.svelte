<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1xq9pboe.css';
import '../../css/c/cpzpl-ooe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1xq9pboe"/><path class="cpzpl-ooe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:imdb" {...props}></Icon>
