<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jakgx-bvd.css';
import '../../css/j/jzt-i4bdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jakgx-bvd"/><path class="jzt-i4bdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:phonon" {...props}></Icon>
