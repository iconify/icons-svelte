<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu4v59b1a.css';
import '../../css/d/dc02pybze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xu4v59b1a"/><path class="dc02pybze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:crunchbase" {...props}></Icon>
