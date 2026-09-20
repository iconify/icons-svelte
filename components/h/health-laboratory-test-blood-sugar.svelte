<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra7rlfb9o.css';
import '../../css/a/a1ufk92yd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ra7rlfb9o"/><path class="a1ufk92yd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:health-laboratory-test-blood-sugar" {...props}></Icon>
