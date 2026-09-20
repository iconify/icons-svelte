<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9n6u8b7u.css';
import '../../css/n/nlmny6bfj.css';
import '../../css/v/vuw91fa1l.css';
import '../../css/e/exs6scbnc.css';
import '../../css/m/mqxvrjcit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9n6u8b7u"/><path class="nlmny6bfj"/><path class="vuw91fa1l"/><path class="exs6scbnc"/><path class="mqxvrjcit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:glm-v" {...props}></Icon>
