<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn7jw0bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cn7jw0bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:at-outline" {...props}></Icon>
