<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwkkdgb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wwkkdgb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:password-pencil-16-solid" {...props}></Icon>
