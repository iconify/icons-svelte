<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng-7dbvkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ng-7dbvkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:back-square-outline" {...props}></Icon>
