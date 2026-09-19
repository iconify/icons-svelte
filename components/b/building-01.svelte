<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oovfznbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oovfznbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:building-01" {...props}></Icon>
