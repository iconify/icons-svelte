<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un_rqmbfz.css';
import '../../css/j/ju2zpyrzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="un_rqmbfz"/><circle class="ju2zpyrzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:information" {...props}></Icon>
