<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqut9yb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqut9yb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:ribbon-fill" {...props}></Icon>
