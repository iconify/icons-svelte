<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5s-gwx6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5s-gwx6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:gem-stone-fill" {...props}></Icon>
