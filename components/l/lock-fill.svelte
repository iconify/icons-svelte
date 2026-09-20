<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk_c8jfkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sk_c8jfkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:lock-fill" {...props}></Icon>
