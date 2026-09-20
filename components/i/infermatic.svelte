<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoqkenqop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uoqkenqop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:infermatic" {...props}></Icon>
