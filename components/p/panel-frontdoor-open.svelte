<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onzcvab0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onzcvab0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:panel-frontdoor-open" {...props}></Icon>
