<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d22wuprbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d22wuprbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:checklist" {...props}></Icon>
