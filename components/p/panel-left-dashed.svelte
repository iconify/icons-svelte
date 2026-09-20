<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyvei5bod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyvei5bod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-left-dashed" {...props}></Icon>
