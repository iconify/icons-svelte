<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnw1z9bjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnw1z9bjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:database-2-fill" {...props}></Icon>
