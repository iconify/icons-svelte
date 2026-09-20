<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1y_zhbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1y_zhbca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mubi" {...props}></Icon>
