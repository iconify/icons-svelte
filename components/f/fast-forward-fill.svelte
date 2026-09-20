<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5bphv0mk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5bphv0mk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:fast-forward-fill" {...props}></Icon>
