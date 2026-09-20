<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn_3pob7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nn_3pob7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:minus-square-fill" {...props}></Icon>
