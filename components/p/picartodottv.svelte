<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7dwd_byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7dwd_byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:picartodottv" {...props}></Icon>
