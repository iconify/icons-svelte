<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhhghx8wo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhhghx8wo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:exclamation-octagon" {...props}></Icon>
