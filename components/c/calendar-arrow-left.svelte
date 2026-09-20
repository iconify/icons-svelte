<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apn_b4pdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apn_b4pdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:calendar-arrow-left" {...props}></Icon>
