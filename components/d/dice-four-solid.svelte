<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w22q1qmkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w22q1qmkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:dice-four-solid" {...props}></Icon>
