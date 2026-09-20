<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5sn6rijz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5sn6rijz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:apple-whole" {...props}></Icon>
