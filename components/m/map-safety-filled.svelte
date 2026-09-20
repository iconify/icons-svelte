<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9orhbcrs.css';
import '../../css/b/bye6f4hdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9orhbcrs"/><path class="bye6f4hdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-safety-filled" {...props}></Icon>
