<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih0nrxghi.css';
import '../../css/q/qy6r87b-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ih0nrxghi"/><path class="qy6r87b-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:left-indent-alt" {...props}></Icon>
