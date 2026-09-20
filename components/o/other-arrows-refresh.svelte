<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdx3qo68o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gdx3qo68o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-arrows-refresh" {...props}></Icon>
