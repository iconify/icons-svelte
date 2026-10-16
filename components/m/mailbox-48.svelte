<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a66xx_uzh.css';
import '../../css/c/c79jlob-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a66xx_uzh"/><path class="c79jlob-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mailbox-48" {...props}></Icon>
