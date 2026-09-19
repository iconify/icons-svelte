<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rem_-jbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":29,"height":24};
const content = `<path class="rem_-jbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:right-align" {...props}></Icon>
