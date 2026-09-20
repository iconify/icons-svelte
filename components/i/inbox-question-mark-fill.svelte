<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_zh3nbon.css';
import '../../css/f/f-euyubsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_zh3nbon"/><path class="f-euyubsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:inbox-question-mark-fill" {...props}></Icon>
