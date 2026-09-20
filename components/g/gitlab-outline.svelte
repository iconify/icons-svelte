<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au3h63b1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="au3h63b1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:gitlab-outline" {...props}></Icon>
