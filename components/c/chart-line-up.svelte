<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azu9p9b0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="azu9p9b0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chart-line-up" {...props}></Icon>
