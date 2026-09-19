<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf211bbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="cf211bbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:file-woff-small-filled" {...props}></Icon>
