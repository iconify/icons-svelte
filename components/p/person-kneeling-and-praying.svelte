<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/regj2beml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="regj2beml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-kneeling-and-praying" {...props}></Icon>
