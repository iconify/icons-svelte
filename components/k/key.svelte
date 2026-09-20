<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4vm18b5j.css';
import '../../css/b/bosvvnbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4vm18b5j"/><path clip-rule="evenodd" class="bosvvnbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:key" {...props}></Icon>
