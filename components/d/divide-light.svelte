<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1-k6-beh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1-k6-beh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:divide-light" {...props}></Icon>
