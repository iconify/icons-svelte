<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8mn3cssj.css';
import '../../css/b/bcaaafv4h.css';
import '../../css/z/z8-thgb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u8mn3cssj"/><path class="bcaaafv4h"/><path class="z8-thgb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ladybird-20-bold" {...props}></Icon>
