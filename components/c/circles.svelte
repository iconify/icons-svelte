<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwvql_bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwvql_bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circles" {...props}></Icon>
