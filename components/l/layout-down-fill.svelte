<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv26_lbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lv26_lbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:layout-down-fill" {...props}></Icon>
