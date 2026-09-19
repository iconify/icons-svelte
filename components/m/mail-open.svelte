<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9qin9rbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j9qin9rbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:mail-open" {...props}></Icon>
