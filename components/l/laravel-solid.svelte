<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ems_ytbdz.css';
import '../../css/x/xwn1thb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ems_ytbdz"/><path clip-rule="evenodd" class="xwn1thb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:laravel-solid" {...props}></Icon>
