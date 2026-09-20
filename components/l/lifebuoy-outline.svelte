<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebc1v__7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ebc1v__7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:lifebuoy-outline" {...props}></Icon>
