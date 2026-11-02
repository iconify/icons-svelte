<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj9jkgb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj9jkgb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-2-fill" {...props}></Icon>
