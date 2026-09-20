<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9k22abrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9k22abrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:lightning-alt" {...props}></Icon>
