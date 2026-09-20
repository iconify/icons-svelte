<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqlaruk5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qqlaruk5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:bug-antivirus-shield-remix" {...props}></Icon>
