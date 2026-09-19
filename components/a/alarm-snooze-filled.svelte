<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1uq_ccag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f1uq_ccag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:alarm-snooze-filled" {...props}></Icon>
