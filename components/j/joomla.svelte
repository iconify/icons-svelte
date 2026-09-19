<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oko04mjqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="oko04mjqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:joomla" {...props}></Icon>
