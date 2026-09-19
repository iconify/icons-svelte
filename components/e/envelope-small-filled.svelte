<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nazj7-39k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="nazj7-39k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:envelope-small-filled" {...props}></Icon>
