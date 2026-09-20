<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zamd5-oru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zamd5-oru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:phone-minus-fill" {...props}></Icon>
