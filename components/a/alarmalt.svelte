<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob0egjsku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="ob0egjsku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:alarmalt" {...props}></Icon>
