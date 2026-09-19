<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e00gdx4ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="e00gdx4ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:arrow-left" {...props}></Icon>
