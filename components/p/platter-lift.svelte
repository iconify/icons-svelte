<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c17c66b6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c17c66b6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:platter-lift" {...props}></Icon>
