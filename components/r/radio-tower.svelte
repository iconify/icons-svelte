<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahur8ibka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ahur8ibka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:radio-tower" {...props}></Icon>
