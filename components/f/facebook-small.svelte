<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj2430bkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="jj2430bkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:facebook-small" {...props}></Icon>
