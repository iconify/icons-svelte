<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2s2eubjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o2s2eubjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:act" {...props}></Icon>
