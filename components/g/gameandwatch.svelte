<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6k6h2o9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6k6h2o9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:gameandwatch" {...props}></Icon>
