<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8nocibwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v8nocibwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:clothes-briefs" {...props}></Icon>
