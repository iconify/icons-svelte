<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmz_rrbpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hmz_rrbpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-contrast" {...props}></Icon>
