<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od73i4b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="od73i4b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:list-timeline" {...props}></Icon>
