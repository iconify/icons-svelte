<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t921sfb1a.css';
import '../../css/g/gh6kuqeme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t921sfb1a"/><path class="gh6kuqeme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dots-line" {...props}></Icon>
