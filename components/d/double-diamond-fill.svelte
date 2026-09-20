<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkgj8db4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkgj8db4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:double-diamond-fill" {...props}></Icon>
