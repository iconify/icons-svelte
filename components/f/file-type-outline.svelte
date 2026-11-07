<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmfzwksnq.css';
import '../../css/d/d25mwn3tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmfzwksnq"/><path clip-rule="evenodd" class="d25mwn3tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-type-outline" {...props}></Icon>
