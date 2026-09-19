<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_-jwob6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b_-jwob6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:logo-google-play" {...props}></Icon>
