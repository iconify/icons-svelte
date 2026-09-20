<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq8l94kmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bq8l94kmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:radar" {...props}></Icon>
