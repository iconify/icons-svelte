<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml_yo8qyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ml_yo8qyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:open-bug-bounty" {...props}></Icon>
