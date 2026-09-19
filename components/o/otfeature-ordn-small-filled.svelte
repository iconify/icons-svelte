<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd29xjbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="pd29xjbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-ordn-small-filled" {...props}></Icon>
