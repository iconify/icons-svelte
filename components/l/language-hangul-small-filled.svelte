<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp1bg9iuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="wp1bg9iuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-hangul-small-filled" {...props}></Icon>
