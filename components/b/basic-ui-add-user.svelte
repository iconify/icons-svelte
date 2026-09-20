<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv1tmnbqm.css';
import '../../css/p/p_f0lhbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yv1tmnbqm"/><path clip-rule="evenodd" class="p_f0lhbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-ui-add-user" {...props}></Icon>
