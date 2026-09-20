<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwf0vrgqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="wwf0vrgqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-round-up-left" {...props}></Icon>
