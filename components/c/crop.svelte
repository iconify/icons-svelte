<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuf5-ng-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uuf5-ng-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:crop" {...props}></Icon>
