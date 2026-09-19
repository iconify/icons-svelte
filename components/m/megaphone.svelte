<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkn1q5bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":32};
const content = `<path class="kkn1q5bew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:megaphone" {...props}></Icon>
