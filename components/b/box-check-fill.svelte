<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzjy1cc-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzjy1cc-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:box-check-fill" {...props}></Icon>
