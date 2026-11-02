<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh__oquew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oh__oquew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hand-helping-fill" {...props}></Icon>
