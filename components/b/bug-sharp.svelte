<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebflwhkmy.css';
import '../../css/o/o98-wvvyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ebflwhkmy"/><path class="o98-wvvyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:bug-sharp" {...props}></Icon>
