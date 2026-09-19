<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw99eqe7z.css';
import '../../css/i/ilsfesr3y.css';
import '../../css/u/uaycyrbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="jw99eqe7z"/><path class="ilsfesr3y"/><path class="uaycyrbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:media-changer-outline-alerted" {...props}></Icon>
