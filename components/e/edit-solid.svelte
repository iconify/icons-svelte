<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnh7j8q2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gnh7j8q2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:edit-solid" {...props}></Icon>
