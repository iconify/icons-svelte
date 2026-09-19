<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyk4aoyft.css';
import '../../css/a/a24z59vtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iyk4aoyft"/><path class="a24z59vtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:direction-ltr-fill-16" {...props}></Icon>
