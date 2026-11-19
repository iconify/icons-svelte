<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz-e1wn7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wz-e1wn7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:ab-test" {...props}></Icon>
