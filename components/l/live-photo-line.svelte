<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etl6gjblu.css';
import '../../css/c/czl4vwb8t.css';
import '../../css/b/bmgtm8_um.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="etl6gjblu"/><path class="czl4vwb8t"/><path class="bmgtm8_um"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:live-photo-line" {...props}></Icon>
