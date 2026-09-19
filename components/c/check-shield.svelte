<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h38or2igg.css';
import '../../css/s/sjerm91lq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h38or2igg"/><path class="sjerm91lq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:check-shield" {...props}></Icon>
