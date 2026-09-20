<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5l1xgljl.css';
import '../../css/e/ec-xsg-ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5l1xgljl"/><path class="ec-xsg-ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cgt" {...props}></Icon>
