<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7p82fban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7p82fban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:double-circle-fill" {...props}></Icon>
