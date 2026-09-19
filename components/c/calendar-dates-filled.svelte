<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5fqdlybr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q5fqdlybr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:calendar-dates-filled" {...props}></Icon>
