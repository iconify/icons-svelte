<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt1xgbbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gt1xgbbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:general-motors" {...props}></Icon>
