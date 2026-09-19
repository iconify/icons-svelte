<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8aw4pb6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b8aw4pb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:play-skip-forward-circle" {...props}></Icon>
