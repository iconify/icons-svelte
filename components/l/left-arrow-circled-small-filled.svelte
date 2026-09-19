<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn1hatb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="qn1hatb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:left-arrow-circled-small-filled" {...props}></Icon>
