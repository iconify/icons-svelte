<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cye1qenss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="cye1qenss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:format-align-right" {...props}></Icon>
