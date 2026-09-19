<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnnwlwbti.css';
import '../../css/y/y4a8f1y-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lnnwlwbti"/><path clip-rule="evenodd" class="y4a8f1y-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:fire-outline" {...props}></Icon>
