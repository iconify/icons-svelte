<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eos9p4b7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eos9p4b7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:home-alt-minus" {...props}></Icon>
