<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxijq36vr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxijq36vr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bathroom-tissue-outline" {...props}></Icon>
