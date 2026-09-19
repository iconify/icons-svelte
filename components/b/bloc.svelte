<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av5liu7sk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":428,"height":512};
const content = `<path class="av5liu7sk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:bloc" {...props}></Icon>
