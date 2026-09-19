<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7vv9abbc.css';
import '../../css/y/yyop1qbid.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline--badged clr-i-outline-path-1--badged f7vv9abbc"/><circle class="clr-i-badge clr-i-outline--badged clr-i-outline-path-2--badged yyop1qbid"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:blocks-group-outline-badged" {...props}></Icon>
