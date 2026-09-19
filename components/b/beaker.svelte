<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to6b26udf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="to6b26udf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:beaker" {...props}></Icon>
