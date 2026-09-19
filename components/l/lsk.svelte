<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwi53wg-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pwi53wg-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:lsk" {...props}></Icon>
