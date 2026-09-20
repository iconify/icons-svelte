<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/daolku9bq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="daolku9bq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:game-controller" {...props}></Icon>
