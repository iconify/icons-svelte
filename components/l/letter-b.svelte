<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekc2a9bdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekc2a9bdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-b" {...props}></Icon>
