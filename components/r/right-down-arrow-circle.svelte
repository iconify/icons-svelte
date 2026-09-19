<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gql3thbcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gql3thbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:right-down-arrow-circle" {...props}></Icon>
