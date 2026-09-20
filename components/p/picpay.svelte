<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fero9_b6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fero9_b6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:picpay" {...props}></Icon>
