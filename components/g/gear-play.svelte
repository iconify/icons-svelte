<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftu55jb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ftu55jb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:gear-play" {...props}></Icon>
