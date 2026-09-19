<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nplhmob-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nplhmob-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:arrow-circle-up-fill" {...props}></Icon>
