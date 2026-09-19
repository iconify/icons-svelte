<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlmnb0b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1025};
const content = `<path class="vlmnb0b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:preview" {...props}></Icon>
