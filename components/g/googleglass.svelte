<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnffa9b1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="mnffa9b1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:googleglass" {...props}></Icon>
