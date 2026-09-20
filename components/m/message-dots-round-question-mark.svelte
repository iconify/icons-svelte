<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/y4ufzepjc.css';
import '../../css/t/tiigb8gda.css';
import '../../css/o/owv4ifbin.css';
import '../../css/i/isdh7ybrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y4ufzepjc"/><path class="tiigb8gda"/><path class="owv4ifbin"/><path class="isdh7ybrm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:message-dots-round-question-mark" {...props}></Icon>
